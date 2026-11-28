<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk08rrbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk08rrbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mic-play" /></template>
