<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eep2siwjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eep2siwjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:puzzle" /></template>
