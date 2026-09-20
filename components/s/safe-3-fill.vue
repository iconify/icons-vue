<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzzgo7biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzzgo7biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:safe-3-fill" /></template>
