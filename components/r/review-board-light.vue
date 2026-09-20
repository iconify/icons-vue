<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe-vlx7fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oe-vlx7fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:review-board-light" /></template>
