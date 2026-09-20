<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8dfe4y1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8dfe4y1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pleroma-dark" /></template>
