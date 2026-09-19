<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z67c-1big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z67c-1big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:phone" /></template>
