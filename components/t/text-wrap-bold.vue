<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk8pohd4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yk8pohd4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-wrap-bold" /></template>
