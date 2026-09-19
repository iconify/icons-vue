<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1vewfb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":16};
const content = `<path class="x1vewfb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:play" /></template>
