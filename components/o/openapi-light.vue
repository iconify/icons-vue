<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd3mqx2ep.css';
import '../../css/s/szghgl-0e.css';
import '../../css/s/sp8ko-bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd3mqx2ep"/><path class="szghgl-0e"/><path class="sp8ko-bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:openapi-light" /></template>
