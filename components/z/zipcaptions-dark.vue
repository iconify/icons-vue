<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwv_ujx8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwv_ujx8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zipcaptions-dark" /></template>
