<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi17097tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="oi17097tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:pubpeer" /></template>
