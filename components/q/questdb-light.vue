<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvy90ydya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvy90ydya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:questdb-light" /></template>
