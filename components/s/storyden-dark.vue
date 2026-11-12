<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmibnzbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmibnzbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storyden-dark" /></template>
