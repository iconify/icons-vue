<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wset72fas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wset72fas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synapse-dark" /></template>
