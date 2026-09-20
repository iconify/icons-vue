<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn8jj9htz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qn8jj9htz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-opni-light" /></template>
