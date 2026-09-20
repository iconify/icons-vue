<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb3s82fnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zb3s82fnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:part-of-circle-3" /></template>
