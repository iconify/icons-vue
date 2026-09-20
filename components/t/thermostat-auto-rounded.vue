<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paioiubvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermostat-auto-rounded" /></template>
<style>
.paioiubvi {
  fill: currentColor;
  d: path("m15.533 10.392l-.914 2.325q-.055.123-.156.203t-.25.08q-.24 0-.366-.187q-.126-.188-.04-.404l3.191-8.223q.036-.09.111-.138T17.275 4h.242q.09 0 .166.048q.075.048.111.138l3.24 8.21q.087.235-.046.42q-.132.184-.373.184q-.148 0-.261-.07t-.17-.219l-.913-2.319zm.296-.8h3.134l-1.536-4.019h-.089zm-10.51 9.244Q4.153 17.67 4.153 16q0-1.046.525-1.959t1.475-1.503V6q0-.846.577-1.423T8.154 4t1.423.577T10.154 6v6.539q.95.59 1.475 1.502T12.154 16q0 1.671-1.164 2.836Q9.825 20 8.153 20t-2.836-1.164M5.154 16h6q0-.744-.4-1.436T9.609 13.33L9.154 13V6q0-.425-.288-.712T8.154 5t-.713.288T7.154 6v7l-.454.33q-.748.541-1.147 1.234q-.4.692-.4 1.436");
}

</style>
