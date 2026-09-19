<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndyg946ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ndyg946ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mapping-hide" /></template>
