<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-4uxpbxq.css';
import '../../css/c/cjzwyi8ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-4uxpbxq"/><path class="cjzwyi8ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticky-light" /></template>
