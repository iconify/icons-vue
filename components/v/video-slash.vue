<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xor048bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xor048bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:video-slash" /></template>
