<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cocew2s-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cocew2s-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:replane" /></template>
