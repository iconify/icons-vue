<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc4wnbbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qc4wnbbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:print" /></template>
