<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umdp1wo1l.css';
import '../../css/x/x1f6fx_5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="umdp1wo1l"/><path class="x1f6fx_5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-rainbow" /></template>
