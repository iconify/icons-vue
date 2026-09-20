<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us0srpbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="us0srpbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-dark" /></template>
