<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkwmo2b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zkwmo2b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:telescope-16" /></template>
