<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gztstl2_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gztstl2_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rotate-counterclockwise-alt-filled" /></template>
