<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m-2e2acrw.css';
import '../../css/d/de1npwusp.css';
import '../../css/y/ykc6yv3ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m-2e2acrw"/><path class="de1npwusp wm-a"/><path class="ykc6yv3ga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pin-duo" /></template>
