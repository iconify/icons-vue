<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hctj1nb7c.css';
import '../../css/q/qxaqxeblh.css';
import '../../css/m/mjuiasbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hctj1nb7c"/><path class="qxaqxeblh"/><path class="mjuiasbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-plus" /></template>
