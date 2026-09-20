<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q262y9b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q262y9b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:orange-isp-light" /></template>
