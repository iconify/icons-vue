<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt7jvlb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt7jvlb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:unfold-vertical" /></template>
