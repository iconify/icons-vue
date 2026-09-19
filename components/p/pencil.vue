<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9_97lbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s9_97lbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:pencil" /></template>
