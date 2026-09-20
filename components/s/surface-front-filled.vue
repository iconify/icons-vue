<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uivcxx24w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uivcxx24w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:surface-front-filled" /></template>
