<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw1ejmbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fw1ejmbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnipoly-dark" /></template>
