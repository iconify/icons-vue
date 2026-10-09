<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-kx1bbug.css';
import '../../css/s/s-tqsqm8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u-kx1bbug"/><path class="s-tqsqm8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:snowboard-20" /></template>
