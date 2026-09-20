<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wica53iwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wica53iwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-longhorn-dark" /></template>
