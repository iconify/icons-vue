<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljv2b8c6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljv2b8c6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meshtastic-dark" /></template>
