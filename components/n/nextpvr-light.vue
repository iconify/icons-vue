<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqc2gxb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqc2gxb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextpvr-light" /></template>
