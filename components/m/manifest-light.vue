<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz3z958ur.css';
import '../../css/n/nxwcidc1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uz3z958ur"/><path class="nxwcidc1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:manifest-light" /></template>
