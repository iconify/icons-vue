<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og5h33zgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="og5h33zgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-k3s" /></template>
