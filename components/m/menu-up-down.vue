<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3q4aactz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="q3q4aactz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:menu-up-down" /></template>
