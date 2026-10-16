<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx2djpbfz.css';
import '../../css/w/w04ysbbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tx2djpbfz"/><path class="w04ysbbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-gibbous-20-bold" /></template>
