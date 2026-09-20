<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uicp4xbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uicp4xbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qzone" /></template>
