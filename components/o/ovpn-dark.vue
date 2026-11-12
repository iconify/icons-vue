<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae56v0u4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae56v0u4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ovpn-dark" /></template>
