<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9zch-ttv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9zch-ttv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notion-light" /></template>
