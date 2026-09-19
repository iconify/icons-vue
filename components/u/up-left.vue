<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pccwcw4ye.css';
import '../../css/a/alckcbcdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pccwcw4ye"/><path class="alckcbcdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:up-left" /></template>
