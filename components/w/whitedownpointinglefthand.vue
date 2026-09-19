<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgsqg7sjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgsqg7sjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitedownpointinglefthand" /></template>
