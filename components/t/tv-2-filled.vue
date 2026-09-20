<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqnmd1o0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqnmd1o0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tv-2-filled" /></template>
