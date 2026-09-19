<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5u-s0bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b5u-s0bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:pie-single-solid" /></template>
