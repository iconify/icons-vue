<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqo7_ubqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fqo7_ubqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-harvester-dark" /></template>
