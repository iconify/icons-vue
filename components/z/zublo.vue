<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpkefj6mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpkefj6mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zublo" /></template>
