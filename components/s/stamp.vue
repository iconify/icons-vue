<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vuvr24b3y.css';
import '../../css/y/y5xaw8b8n.css';
import '../../css/e/eyr57ibcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vuvr24b3y wm-a"/><path class="y5xaw8b8n"/><path class="eyr57ibcj wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stamp" /></template>
