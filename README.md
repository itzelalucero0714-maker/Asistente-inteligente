def asistente(texto):
    texto = texto.lower()
    
    if "dolor" in texto:
        return "Te recomendamos agendar una cita."
    elif "fiebre" in texto:
        return "Podrías necesitar atención médica."
    elif "tos" in texto:
        return "Podría ser gripe, consulta a un médico."
    else:
        return "Consulta con un especialista."

# Simulación
entrada = input("Describe tu problema: ")
print(asistente(entrada))
