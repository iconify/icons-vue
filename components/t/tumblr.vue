<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8z9413sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":272,"height":432};
const content = `<path class="p8z9413sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tumblr" /></template>
