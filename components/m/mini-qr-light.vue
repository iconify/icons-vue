<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv2s6nbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rv2s6nbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mini-qr-light" /></template>
