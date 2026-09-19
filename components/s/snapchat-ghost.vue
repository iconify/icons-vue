<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onnfaq1uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1536};
const content = `<path class="onnfaq1uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:snapchat-ghost" /></template>
