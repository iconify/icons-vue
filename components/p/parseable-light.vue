<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioq9ntycb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ioq9ntycb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:parseable-light" /></template>
