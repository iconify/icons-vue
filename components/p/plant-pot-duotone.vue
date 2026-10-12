<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ly7qoj00u.css';
import '../../css/z/z6cin8b0o.css';
import '../../css/f/fdp43wbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ly7qoj00u"/><path class="z6cin8b0o"/><path class="fdp43wbff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:plant-pot-duotone" /></template>
