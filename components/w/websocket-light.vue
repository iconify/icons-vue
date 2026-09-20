<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ies5kpvvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ies5kpvvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:websocket-light" /></template>
