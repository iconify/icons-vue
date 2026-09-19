<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esxpy3bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":916};
const content = `<path class="esxpy3bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:observatory" /></template>
