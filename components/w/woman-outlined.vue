<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy3q97bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iy3q97bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:woman-outlined" /></template>
