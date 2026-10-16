<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw3g6zbcc.css';
import '../../css/c/cbyfxzbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lw3g6zbcc"/><path class="cbyfxzbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipeline-pig-20-bold" /></template>
