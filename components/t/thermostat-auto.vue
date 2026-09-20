<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq8w8ac3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermostat-auto" /></template>
<style>
.aq8w8ac3a {
  fill: currentColor;
  d: path("m13.567 13l3.51-9h.639l3.559 9h-.973l-1.03-2.608h-3.74L14.503 13zm2.262-3.408h3.135l-1.537-4.019h-.088zm-10.51 9.244Q4.153 17.67 4.153 16q0-1.046.525-1.959t1.475-1.503V6q0-.846.577-1.423T8.154 4t1.423.577T10.154 6v6.539q.95.59 1.475 1.502T12.154 16q0 1.671-1.164 2.836Q9.825 20 8.153 20t-2.836-1.164M5.154 16h6q0-.744-.4-1.436T9.609 13.33L9.154 13V6q0-.425-.288-.712T8.154 5t-.713.288T7.154 6v7l-.454.33q-.748.541-1.147 1.234q-.4.692-.4 1.436");
}

</style>
