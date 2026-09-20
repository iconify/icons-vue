<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx2jtu4ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zx2jtu4ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traefik-manager-dark" /></template>
