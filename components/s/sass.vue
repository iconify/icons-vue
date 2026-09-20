<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv0x06bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zv0x06bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sass" /></template>
