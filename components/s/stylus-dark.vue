<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqeiku3dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqeiku3dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stylus-dark" /></template>
