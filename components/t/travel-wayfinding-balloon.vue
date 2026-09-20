<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxpo9jkdm.css';
import '../../css/x/xg28s7bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zxpo9jkdm"/><path class="xg28s7bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:travel-wayfinding-balloon" /></template>
