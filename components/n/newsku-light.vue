<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u671_1o_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u671_1o_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newsku-light" /></template>
