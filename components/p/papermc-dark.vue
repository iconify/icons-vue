<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf_0tfbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sf_0tfbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-dark" /></template>
