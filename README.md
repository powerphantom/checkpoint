#include "dork.h"
#include "game.h"

//may need to update includes with load/save and play


void checkpoint:: checkpoint (Display var){

	int numSteps = var.GetSteps();

	if ((numSteps%25) == 0){

		Save();	//call save function

	}

}
