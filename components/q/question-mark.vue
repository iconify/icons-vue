<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk136onmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lk136onmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:question-mark" /></template>
