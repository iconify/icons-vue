<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xksh8usvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xksh8usvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-down-filled" /></template>
