<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryz1rabnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ryz1rabnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:volume-mute" /></template>
