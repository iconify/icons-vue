<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czmi4cb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czmi4cb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pangolin-light" /></template>
