<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7f5jf0ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="y7f5jf0ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:sort-up" /></template>
