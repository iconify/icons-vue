<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6m9uabxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a6m9uabxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:raised-curb-with-exclamation-point" /></template>
