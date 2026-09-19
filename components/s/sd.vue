<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhe0cabnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hhe0cabnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sd" /></template>
