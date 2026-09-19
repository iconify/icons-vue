<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2iyb1b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":641,"height":1024};
const content = `<path class="c2iyb1b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:resizevertical" /></template>
