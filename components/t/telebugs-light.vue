<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb7coib4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jb7coib4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:telebugs-light" /></template>
