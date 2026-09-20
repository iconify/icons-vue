<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scsp4ibpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="scsp4ibpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snowshare-light" /></template>
