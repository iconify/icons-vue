<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ebc0dyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_ebc0dyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-k3os-light" /></template>
