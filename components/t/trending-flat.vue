<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6u8fjbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="c6u8fjbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:trending-flat" /></template>
