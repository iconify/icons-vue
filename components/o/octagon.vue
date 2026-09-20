<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec73mxbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ec73mxbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:octagon" /></template>
