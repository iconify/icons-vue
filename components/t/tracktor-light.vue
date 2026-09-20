<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piigrn6ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="piigrn6ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tracktor-light" /></template>
