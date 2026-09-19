<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkd07cs8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bkd07cs8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:padding-top" /></template>
