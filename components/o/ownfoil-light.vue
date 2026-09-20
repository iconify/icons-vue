<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydol1y82a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ydol1y82a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ownfoil-light" /></template>
