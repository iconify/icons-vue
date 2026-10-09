<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts501wnao.css';
import '../../css/m/ma0bxjbgr.css';
import '../../css/m/mxvrl8fhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ts501wnao"/><path class="ma0bxjbgr"/><path class="mxvrl8fhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:package-20" /></template>
