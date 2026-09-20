<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fox-zjbbr.css';
import '../../css/t/tc50lygvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fox-zjbbr"/><path class="tc50lygvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reitti-dark" /></template>
