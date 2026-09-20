<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xijeu059d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xijeu059d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netboot-xyz-dark" /></template>
