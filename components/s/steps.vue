<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efdeyex5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:steps" /></template>
<style>
.efdeyex5h {
  fill: currentColor;
  d: path("M5.4 10H3.104q.062-.312.195-.605q.134-.293.34-.574l3.869-5.15q.213-.286.56-.378q.348-.091.67.086l.72.35q.275.14.408.375q.134.234.134.521v3.389l3.1-.802q.385-.104.72.091t.469.574l1.702 5.112l4.423 4.423q.345.346.466.748q.12.402.12.84q0 .752-.49 1.304t-1.233.633h-.635L8.504 11.24q-.648-.599-1.446-.92T5.4 10m8.75 11q-.558 0-1.07-.198q-.51-.198-.932-.583l-8.125-7.375q-.417-.367-.65-.847t-.3-.997H5.4q.671 0 1.305.239q.634.238 1.116.72L17.248 21z");
}

</style>
