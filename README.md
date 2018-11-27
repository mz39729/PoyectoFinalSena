<html>
    <head>
        <meta name="viewport" />
        <meta name="utf-8"/>
         <meta name="description" content="Encuestadora"/>
	    <title> FICHA PSICOSOCIAL</title>
	    <link rel="stylesheet" href="css/Style.css"/>
    </head>
    <body>
	    <header>
		    <h1></h1>
		    
		    <img src="img/logo.jpg"/>
		</header>
		    
            
            <div class="">
                 <h2>IDENTIFICACION</h2> 
                 
                  <label>-nombres y Apellidos</label> <input type="text" name="NyP">
		          <label>-Lugar y Fecha de Nacimiento:</label><input type="text" name="LyF">
		           <label>-Edad</label><input type="text" name="edad">
		          <label>-Direccion Permanente:</label><input type="text" name="Direccion">
		          <label>-Telefono:</label><input type="text" name="Tel">
		          <label>-Barrio:</label><input type="text" name="Barrio">
		          <label>-Municipio:</label><input type="text" name="Municipio">
		         
				  <label>-Estado Civil:</label>
				 <select name="Estado Civil:">
				<option>Soltero</option>
				<option>Casado </option>
				<option> U.libre </option>
				<option> Otro </option>
				</select>
				
		          <label>-No Hijo:</label><input type="text" name="nHijo">
		          <label>-No de personas:</label><input type="text" name="NPer">
            </div>
        
            
            <div class="">
               <h2>DATOS FAMILIARES</h2> 
               
               <label>-No De Personas Con Quien Vive:</label><input type="text" name="Npers">
               <label>-Parentescos:</label><input type="text" name="Parentescos">
               <label>-Nombre del Padre:</label><input type="text" name="Npadre">
               <label>-Nombre de la Madre:</label><input type="text" name="Nmadre">
				<label>-Estado Civil De Los Padres :</label>
				 <select name="Estado Padres">

				<option>Soltero</option>

				<option>Casado </option>

				<option> U.libre </option>

				<option> Otro </option>

				</select>
               <label>-Ocupacion Del Padre:</label><input type="text" name="Omadre">
               <label>-Trabaja Actualmente:</label>
               <label>-Ocupacion De La Madre:</label>
               <label>-Trabaja Actualmente:</label>
			   <select name="Trabaja">

				<option>SI</option>

				<option>NO </option>

				</select>
				
               <label>-No Hermanos:</label><input type="text" name="NoH">
               <label>-Lugar Que Ocupa Entre Sus Hermanos:</label><input type="text" name="Lher">
               <label>-Se Utiliza El Dialogo Entre Los Mienbros De La Familia: </label>
			    <select name="Dialogo">

				<option>Siempre</option>

				<option>Aveces</option>

				<option>Nunca </option>
				
				</select>
			   
               
            </div>
           
           
           <div class="">
           <h2>SALUD Y CONDICIONES FISICAS </h2>
           
           <label>-Que nefermedades ha padecido en los ultimos 6 meses:</label>
           
           <label>-En este momento esta tomando algun tipo de droga: </label>
		    <select name="Droga">

				<option>SI</option>

				<option>NO </option>

				</select>
		 <label>Cual</label></label><input type="text" name="CDroga">
				
		 
          <label> algún miembro de la familia padece o ha padecido de alguna enfermedad: </label>     
		  <select name="PEnfermedad">

				<option>SI</option>

				<option>NO </option>

				</select>
           <label>-de que tipo:</label></label><input type="text" name="TEnfermedad">
        </div>
            
            
            
            
            
            <div class="">
               <h2> ASPECTOS DE LA VIVIENDO</h2>
               
                <label>-Estrato:</label><input type="text" name="Estrato">
                <label>Tipo de vivienda:</label>
				<select name="TVivienda">

				<option>CASA</option>

				<option>APARTAMENTO</option>
				
				<option>PIEZA</option>
				
				<option>PENSIONADO</option>
				
				<option>INVASION</option>

				</select>				
				
                <label>Clase de vivienda:Familiar       Arrendada    Propia    No de habitaciones</label>     
				<select name="Cvivienda">

				<option>Arrendada</option>

				<option>Propia</option>

				</select>		
				<label> No de Habitaciones </label> <input type="text" name="No">				
				
                <label>Servicios publicos con que cuenta la vivienda: AGUA    LUZ    GAS    ALCANTARILLADO    TEL   TVCABLE    OTRO</label> 

				<label><input type="checkbox" id="cbox1" value="first_checkbox"> AGUA</label><br>
				<label><input type="checkbox" id="cbox2" value="first_checkbox"> LUZ</label><br>
				<label><input type="checkbox" id="cbox3" value="first_checkbox"> GAS</label><br>
				<label><input type="checkbox" id="cbox1" value="first_checkbox"> ALCANTARILLADO</label><br>
				<label><input type="checkbox" id="cbox1" value="first_checkbox"> TELEFONO</label><br>
				<label><input type="checkbox" id="cbox1" value="first_checkbox"> T.V CABLE</label><br>
				<label><input type="checkbox" id="cbox1" value="first_checkbox"> OTRO</label><br>
				
            </div>
        
		       


             <div class="">
               
                <h2>RELACIONES FAMILIARES</h2>
                 <label>¿Como son las relaciones con tus padres? </label>
				 <select name="Cvivienda">

				<option>BUENAS</option>

				<option>REGULARES</option>
				
				<option>MALAS</option>

				</select>		
				<label>Observaciones:</label> <input type="text"  name="Observaciones">
                 
                 
             </div>

             
             
             
             
             <div class="">
                <h2>ASPECTO ECONOMICO</h2>
                
                 <label>Los ingresos de su hogar depende de:</label>
				 <label><input type="checkbox" id="cbox01" value="first_checkbox"> PADRE</label><br>
				<label><input type="checkbox" id="cbox02" value="first_checkbox">MADRE</label><br>
				<label><input type="checkbox" id="cbox03" value="first_checkbox">OTRO</label><br>
				 
                 <label>De quien depende economicamente usted:</label><input type="text" name="depende">	
                                 
                 <label>El medio de transporte utilizando por usted para llegar al SENA es:</label></label><input type="text" name="Mtrasporte">	        
                 <label>Con cuentas rutas de buses cuenta usted para llegar al SENA:</label><input type="text" name="Crutas">
				 <label>Cuales:</label></label><input type="text" name="Cuales">	     
                 <label>son suficientes los ingresos para cubrir las necesidades basicas:</label>
				 
				 <select name="Suficiente">

				<option>Si</option>

				<option>No</option>

				</select>	
                 <label>¿Porque?</label></label><input type="text" name="Xq">	
                   
             </div>
             <div class="">
                 <h2>ASPECTO PSICOLOGICO</h2>
                 
                 <label>Como utilizan los jovenes de su barrio el tiempo libre:</label> <input type="text" name="Tjovenes">
                 
                 <label>En que actividades ocupan usted el tiempo libre:</label><input type="text"  name="tActividades">
                 <label>Practica algun deporte: </label>   
				<select name="Tdeporte">

				<option>SI</option>

				<option>NO </option>

				</select>				 

				 <label> cual</label><input type="text"  name="Cual">
				 
                     <label>Pertenece a alguna asociacion: </label>   
				<select name="Asociacion">
				<option>Si</option>
				<option>No</option>
				</select>						 
					 
					 <label>cual</label><input type="text" name="Cual2">	
					 
                 <label>Que actividades desarrollabas antes de entrar al SENA:</label><input type="text" name="Dactividades">	
				 
                 <label>Ha sentido curiosidad por conseguir droga:</label>
				  <select name="Curiosidad">
				<option>Si</option>
				<option>No</option>
				</select>	
                 <label>Tienes amigos que consumen droga:</label>
				  <select name="Amigos-Drogas">

				<option>Si</option>

				<option>No</option>

				</select>	
				 
                <label> Ha logrado alguna meta que deseaba alcanzar:</label>
				 <select name="Meta">

				<option>Si</option>

				<option>No</option>

				</select>	

				<label>cual</label><input type="text" name="Cual3">	
                 <label>Le han dicho que tiene una personailidad agradable:</label>   
				<select name="Personalidad">

				<option>Si</option>

				<option>No</option>

				</select>					 
				 <label> ¿Porque?</label><input type="text" name="Xq1">	
                 <label>Se adapto facilmente a los compañeros de su curso:</label>  
				<select name="Adapto">

				<option>Si</option>

				<option>No</option>

				</select>					 
				 <label>¿Porque?</label><input type="text" name="Xq2">	
                 <label>Tomas sus desiciones por si mismo: si     no</label>
				  <select name="Desiciones">

				<option>Si</option>

				<option>No</option>

				</select>	
                 <label>Presionado por alguien:</label>
				  <select name="Presionado">

				<option>Si</option>

				<option>No</option>

				</select>	
                 <label>¿se encuentra afiliado a una entidad prestadora de servicios de salud?:</label>
				  <select name="Afiliado">

				<option>Si</option>

				<option>No</option>

				</select>	
                 <label>Sisben</label><input type="text" name="Sisben">	
				 <label>Cual</label><input type="text" name="Cual4">	
             </div>
              <div class="">
                  <h2>Otros</h2>
                  <label>¿Recibe algun apoyo del gobierno?:</label>
				<select name="AGobierno">

				<option>Si</option>

				<option>No</option>

				</select>					  
				  
				  <label>cual</label><input type="text" name="Cual5">	
                 
              </div>

		
		<footer>
		
		</footer>
        
    </body>

</html>
