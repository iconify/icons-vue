<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koj4gublb.css';
import '../../css/o/ofw11lk8d.css';
import '../../css/y/y6rebfbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="koj4gublb"/><path class="ofw11lk8d"/><path class="y6rebfbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:password-pusher" /></template>
