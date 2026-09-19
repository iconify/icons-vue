<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4dy5ebqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k4dy5ebqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:move" /></template>
