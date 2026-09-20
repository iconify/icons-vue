<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdt9a3kty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qdt9a3kty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milk-carton-and-apple-and-yen-yuan" /></template>
