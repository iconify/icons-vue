<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxmplahaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dxmplahaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:restreamer" /></template>
