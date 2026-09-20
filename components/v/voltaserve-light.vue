<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbcg6dbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbcg6dbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voltaserve-light" /></template>
