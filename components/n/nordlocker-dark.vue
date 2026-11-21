<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0cf-zb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l0cf-zb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nordlocker-dark" /></template>
