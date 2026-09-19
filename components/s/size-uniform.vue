<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9ge0xych.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b d9ge0xych"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:size-uniform" /></template>
