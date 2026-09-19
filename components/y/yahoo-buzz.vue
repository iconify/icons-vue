<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmhsfe4-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":488};
const content = `<path class="dmhsfe4-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:yahoo-buzz" /></template>
