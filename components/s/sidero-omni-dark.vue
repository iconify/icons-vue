<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udy4foket.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="udy4foket"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sidero-omni-dark" /></template>
