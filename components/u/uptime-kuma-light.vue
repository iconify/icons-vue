<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkwa3_bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gkwa3_bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptime-kuma-light" /></template>
