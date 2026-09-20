<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-yr9xtxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z-yr9xtxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sugarcane-stalk-with-top-leaves" /></template>
