<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlk5ymyap.css';
import '../../css/i/i27tkhlqe.css';
import '../../css/x/x6k9lb6mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGJIdMf21m" viewBox="0 0 342 234"><path class="vlk5ymyap"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 4440"/></path><path class="i27tkhlqe"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 2640"/></path></symbol></defs><use width="342" height="234" href="#SVGJIdMf21m" transform="translate(85 139)"/><path class="x6k9lb6mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:wind-beaufort-11" /></template>
