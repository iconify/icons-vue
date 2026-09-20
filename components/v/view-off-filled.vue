<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7v0rzbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y7v0rzbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:view-off-filled" /></template>
