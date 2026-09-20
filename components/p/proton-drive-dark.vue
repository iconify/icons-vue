<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieqwf_b3i.css';
import '../../css/y/yasd2p6xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ieqwf_b3i"/><path class="yasd2p6xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-drive-dark" /></template>
