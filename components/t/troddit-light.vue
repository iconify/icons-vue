<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsjgm3bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lsjgm3bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:troddit-light" /></template>
