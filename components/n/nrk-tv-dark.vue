<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-qr9ac1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-qr9ac1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nrk-tv-dark" /></template>
