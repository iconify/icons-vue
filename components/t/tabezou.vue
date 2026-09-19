<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n702l_a5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1229,"height":677};
const content = `<path class="n702l_a5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:tabezou" /></template>
