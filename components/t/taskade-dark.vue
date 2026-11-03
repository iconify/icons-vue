<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a52e49pvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a52e49pvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:taskade-dark" /></template>
