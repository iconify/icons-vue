<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umdmixbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="umdmixbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rackula-dark" /></template>
