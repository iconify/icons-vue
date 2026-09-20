<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvcj8vpcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvcj8vpcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ugreen-nas-dark" /></template>
