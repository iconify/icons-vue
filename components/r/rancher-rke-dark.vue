<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imgt25i8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imgt25i8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-rke-dark" /></template>
