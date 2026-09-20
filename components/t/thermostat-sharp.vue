<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aym9c0brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermostat-sharp" /></template>
<style>
.aym9c0brk {
  fill: currentColor;
  d: path("M12.077 10.5v-1h4.846v1zm0-3.77v-1h7.846v1zM5.318 18.837Q4.154 17.67 4.154 16q0-1.046.525-1.959t1.475-1.503V6q0-.846.577-1.423T8.154 4t1.423.577T10.154 6v6.539q.95.59 1.475 1.502T12.154 16q0 1.671-1.164 2.836Q9.825 20 8.153 20t-2.836-1.164M5.154 16h6q0-.744-.4-1.436T9.609 13.33L9.154 13V6q0-.425-.288-.712T8.154 5t-.713.288T7.154 6v7l-.454.33q-.748.541-1.147 1.234q-.4.692-.4 1.436");
}

</style>
