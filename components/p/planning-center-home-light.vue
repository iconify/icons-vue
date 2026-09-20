<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9egjfbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9egjfbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-home-light" /></template>
