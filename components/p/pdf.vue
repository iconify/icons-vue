<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zto3li8fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zto3li8fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pdf" /></template>
