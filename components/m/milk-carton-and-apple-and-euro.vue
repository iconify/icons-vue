<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5b2ksb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n5b2ksb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milk-carton-and-apple-and-euro" /></template>
