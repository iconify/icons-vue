<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b61vx_bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b61vx_bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:smileys-happy" /></template>
