<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr9aydbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wr9aydbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smallstep-light" /></template>
