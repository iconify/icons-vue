<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deto26p-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="deto26p-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:owntracks-dark" /></template>
