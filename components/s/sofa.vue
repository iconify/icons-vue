<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es01b9v3e.css';
import '../../css/e/eqsgj0zkv.css';
import '../../css/m/mz31awbam.css';
import '../../css/p/pvx_7mjiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es01b9v3e"/><path class="eqsgj0zkv"/><path class="mz31awbam"/><path class="pvx_7mjiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sofa" /></template>
