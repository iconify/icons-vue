<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzy5zvgku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzy5zvgku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swizzin" /></template>
