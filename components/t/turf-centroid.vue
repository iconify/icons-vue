<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xezhn6bls.css';
import '../../css/o/oxb1cbk0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="xezhn6bls"/><path class="oxb1cbk0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-centroid" /></template>
