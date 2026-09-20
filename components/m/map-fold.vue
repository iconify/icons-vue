<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yas_40bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yas_40bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:map-fold" /></template>
