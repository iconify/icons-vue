<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_p2sqbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b_p2sqbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-cart" /></template>
