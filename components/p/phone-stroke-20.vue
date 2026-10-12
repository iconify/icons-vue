<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqyj3bfjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lqyj3bfjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-stroke-20" /></template>
