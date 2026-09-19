<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm5q7xb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="lm5q7xb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tv" /></template>
