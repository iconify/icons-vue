<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6b1zhbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="k6b1zhbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-3" /></template>
