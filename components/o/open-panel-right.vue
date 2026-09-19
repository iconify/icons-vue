<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh99os3ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dh99os3ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:open-panel-right" /></template>
