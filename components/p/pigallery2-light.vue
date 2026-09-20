<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzncdpg-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xzncdpg-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pigallery2-light" /></template>
