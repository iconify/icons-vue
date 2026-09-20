<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa0qmzb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xa0qmzb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:scroll-solid" /></template>
