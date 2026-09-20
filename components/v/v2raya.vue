<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcc91_nac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xcc91_nac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:v2raya" /></template>
