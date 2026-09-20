<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn427hbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1537,"height":1537};
const content = `<path class="rn427hbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-direction-n" /></template>
