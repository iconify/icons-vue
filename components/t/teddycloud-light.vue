<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd8d_bcwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bd8d_bcwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teddycloud-light" /></template>
