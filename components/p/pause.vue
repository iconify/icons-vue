<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdws16bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdws16bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pause" /></template>
