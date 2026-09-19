<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr_4ze5bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":512};
const content = `<path class="yr_4ze5bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:wine-glass" /></template>
