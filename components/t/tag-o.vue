<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yob_hi-cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yob_hi-cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:tag-o" /></template>
