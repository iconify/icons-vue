<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yva4x7ini.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yva4x7ini"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-opni-dark" /></template>
