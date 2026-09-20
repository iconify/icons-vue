<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgrpdcbuo.css';
import '../../css/z/zl1t5ibdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fgrpdcbuo"/><path class="zl1t5ibdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:phone-signal-full" /></template>
