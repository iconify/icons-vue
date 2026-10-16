<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/japh1-c2n.css';
import '../../css/q/qhxqg70ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="japh1-c2n"/><path class="qhxqg70ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-search-20-bold" /></template>
