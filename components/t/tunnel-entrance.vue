<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6nle-lrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k6nle-lrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tunnel-entrance" /></template>
