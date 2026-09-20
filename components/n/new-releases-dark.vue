<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_i6csbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_i6csbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:new-releases-dark" /></template>
