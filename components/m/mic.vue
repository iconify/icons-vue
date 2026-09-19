<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd39-q0pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":560,"height":850};
const content = `<path class="hd39-q0pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:mic" /></template>
