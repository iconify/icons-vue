<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry68nbwkv.css';
import '../../css/b/b09d1x-lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ry68nbwkv"/><path class="b09d1x-lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:print-solid" /></template>
