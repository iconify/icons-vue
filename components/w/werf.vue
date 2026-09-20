<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oobshmhmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":111};
const content = `<path class="oobshmhmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:werf" /></template>
