<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbe_w6b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kbe_w6b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nine-point-star-outline-on-square" /></template>
