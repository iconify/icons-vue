<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjxa-7b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hjxa-7b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-longhorn" /></template>
