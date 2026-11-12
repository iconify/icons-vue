<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r84g82b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r84g82b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextbeats-dark" /></template>
