<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv8sn4hcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hv8sn4hcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-hole-dark" /></template>
