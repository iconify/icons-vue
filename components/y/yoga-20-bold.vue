<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0h130b3n.css';
import '../../css/f/fml2kccmr.css';
import '../../css/s/se5adobpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b0h130b3n"/><path class="fml2kccmr"/><path class="se5adobpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:yoga-20-bold" /></template>
