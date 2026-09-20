<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l886_s5ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="l886_s5ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:text-image" /></template>
