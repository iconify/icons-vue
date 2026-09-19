<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swmo9bk_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swmo9bk_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:registered" /></template>
