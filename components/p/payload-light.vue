<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l97ms5bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l97ms5bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:payload-light" /></template>
