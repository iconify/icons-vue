<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we9iw4fnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we9iw4fnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-pointer" /></template>
