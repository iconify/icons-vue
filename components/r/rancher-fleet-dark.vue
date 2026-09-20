<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0ooadc2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a0ooadc2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-fleet-dark" /></template>
