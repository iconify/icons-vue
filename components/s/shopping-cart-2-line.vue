<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4l3vs4aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4l3vs4aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-cart-2-line" /></template>
