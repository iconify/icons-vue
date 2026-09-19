<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpe7uw1fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zpe7uw1fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:triangle" /></template>
