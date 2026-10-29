<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gh1_hobdv.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/s/szpavsbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gh1_hobdv wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="szpavsbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mithai-box-blueprint" /></template>
