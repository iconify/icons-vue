<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqb087b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="aqb087b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:minus-box" /></template>
