<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1078ebcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:weight-sharp" /></template>
<style>
.e1078ebcv {
  fill: currentColor;
  d: path("M12 8q.425 0 .713-.288T13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8M4.835 20L6.546 8h3.745q-.133-.212-.212-.468Q10 7.275 10 7q0-.846.577-1.423T12 5t1.423.577T14 7q0 .275-.079.532q-.079.256-.211.468h3.744l1.711 12z");
}

</style>
