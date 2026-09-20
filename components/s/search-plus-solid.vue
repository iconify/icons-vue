<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3-f0t6_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a3-f0t6_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:search-plus-solid" /></template>
