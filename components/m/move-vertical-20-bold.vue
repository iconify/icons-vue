<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8lzt5lna.css';
import '../../css/m/mvzjp1byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x8lzt5lna"/><path class="mvzjp1byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-vertical-20-bold" /></template>
