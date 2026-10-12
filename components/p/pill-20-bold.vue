<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j66ia2m5n.css';
import '../../css/u/uuavj04rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j66ia2m5n"/><path class="uuavj04rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pill-20-bold" /></template>
