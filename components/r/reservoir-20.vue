<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppjx4_bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ppjx4_bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reservoir-20" /></template>
