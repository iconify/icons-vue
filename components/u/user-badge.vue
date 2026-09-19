<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwr6lqb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwr6lqb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:user-badge" /></template>
