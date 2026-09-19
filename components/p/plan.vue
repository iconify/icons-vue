<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxf8dlbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxf8dlbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:plan" /></template>
