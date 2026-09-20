<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2nx_3s3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2nx_3s3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentofu-dark" /></template>
