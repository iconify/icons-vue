<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyc2w9b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jyc2w9b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-below" /></template>
