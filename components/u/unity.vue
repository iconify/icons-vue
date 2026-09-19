<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb52r_b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hb52r_b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:unity" /></template>
