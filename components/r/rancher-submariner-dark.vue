<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbr5r4bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbr5r4bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-submariner-dark" /></template>
