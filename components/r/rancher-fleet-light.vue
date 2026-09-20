<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya901k8pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ya901k8pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-fleet-light" /></template>
