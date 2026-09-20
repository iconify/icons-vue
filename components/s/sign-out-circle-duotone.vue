<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cbzvvub2o.css';
import '../../css/m/m162ywbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle transform="matrix(0 -1 -1 0 22 19)" class="cbzvvub2o"/><path class="m162ywbyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sign-out-circle-duotone" /></template>
