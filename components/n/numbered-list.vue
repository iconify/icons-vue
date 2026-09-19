<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql53qehak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ql53qehak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:numbered-list" /></template>
