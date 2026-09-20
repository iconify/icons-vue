<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc1fifbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yc1fifbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:refresh" /></template>
