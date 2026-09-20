<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4ie978fy.css';
import '../../css/s/si4ma1_ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u4ie978fy"/><path class="si4ma1_ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quickstack" /></template>
