<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmex_vr6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kmex_vr6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-submariner" /></template>
