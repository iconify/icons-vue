<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/m/m6qks8uby.css';
import '../../css/s/si9smc6kz.css';
import '../../css/v/vp529xjks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="m6qks8uby"/><path class="si9smc6kz"/><path class="vp529xjks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:thermometer-snowflake" /></template>
