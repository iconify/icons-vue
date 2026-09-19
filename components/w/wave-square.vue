<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy69faciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="wy69faciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:wave-square" /></template>
