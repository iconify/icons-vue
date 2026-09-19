<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzl7qhbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzl7qhbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:unfold-less" /></template>
