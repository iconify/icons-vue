<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c005r7bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c005r7bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trending-down-fill" /></template>
