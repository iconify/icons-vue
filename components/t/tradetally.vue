<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrtx0ebqp.css';
import '../../css/a/a74kpfbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zrtx0ebqp"/><path class="a74kpfbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tradetally" /></template>
