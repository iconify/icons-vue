<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u63q-cboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u63q-cboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spinnerr-light" /></template>
