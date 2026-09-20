<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljvmnibwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljvmnibwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:npr-light" /></template>
