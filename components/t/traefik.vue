<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdm1m0bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdm1m0bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traefik" /></template>
