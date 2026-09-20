<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppos_pjtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ppos_pjtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:network-device-play" /></template>
