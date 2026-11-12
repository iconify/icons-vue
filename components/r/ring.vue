<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yro947b0c.css';
import '../../css/l/lhh1z-yfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yro947b0c"/><circle class="lhh1z-yfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ring" /></template>
