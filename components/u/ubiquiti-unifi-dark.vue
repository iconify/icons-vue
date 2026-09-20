<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_9orj6ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_9orj6ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ubiquiti-unifi-dark" /></template>
