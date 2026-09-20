<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-gq_fbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y-gq_fbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wakapi" /></template>
