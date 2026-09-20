<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b40ptn0xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b40ptn0xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:mountain-15" /></template>
