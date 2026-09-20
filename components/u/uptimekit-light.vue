<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-e1ixbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-e1ixbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptimekit-light" /></template>
