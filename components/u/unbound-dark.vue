<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjxj3py5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fjxj3py5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unbound-dark" /></template>
