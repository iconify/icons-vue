<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyvy9zbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uyvy9zbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nordlocker-light" /></template>
