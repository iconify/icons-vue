<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bryv9-bhw.css';
import '../../css/e/eakappb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bryv9-bhw"/><path class="eakappb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rack-and-pinion-20-bold" /></template>
