<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc-ok1ayh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zc-ok1ayh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:pixelfed" /></template>
