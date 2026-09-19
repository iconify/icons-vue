<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po5zkhctu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="po5zkhctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:mixer" /></template>
