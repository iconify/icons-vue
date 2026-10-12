<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utoyqy2ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="utoyqy2ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shapes-stroke-20" /></template>
