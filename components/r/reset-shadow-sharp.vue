<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwyhrhcje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reset-shadow-sharp" /></template>
<style>
.fwyhrhcje {
  fill: currentColor;
  d: path("M13.318 19.682Q12 18.363 12 16.5t1.318-3.182T16.5 12t3.182 1.318T21 16.5t-1.318 3.182T16.5 21t-3.182-1.318m3.163.299q-.558-.747-.878-1.612t-.32-1.869t.323-1.879T16.48 13q-1.443 0-2.462 1.029T13 16.5t1.02 2.462t2.46 1.019m3.141-10.366h-1.036q-.727-2.027-2.504-3.32T12 5Q9.075 5 7.038 7.038T5 12q0 2.108 1.11 3.79Q7.222 17.474 9 18.309V15h1v5H5v-1h3.312q-1.916-1-3.114-2.851T4 12q0-1.664.626-3.118T6.34 6.34t2.542-1.714T12 4q2.706 0 4.778 1.584q2.072 1.583 2.843 4.032");
}

</style>
