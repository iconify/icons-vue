<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/q/qsi2q6bmn.css';
import '../../css/x/xmpu4fb3w.css';
import '../../css/p/pjawsvbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="qsi2q6bmn wm-shadow"/><path class="wm-shadow xmpu4fb3w"/><path class="pjawsvbom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:utensils-crossed" /></template>
