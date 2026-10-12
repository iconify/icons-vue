<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qv-63pbce.css';
import '../../css/y/y-oiv4box.css';
import '../../css/h/hnbud8kdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qv-63pbce"/><path class="y-oiv4box"/><path class="hnbud8kdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:printer-check-duotone" /></template>
