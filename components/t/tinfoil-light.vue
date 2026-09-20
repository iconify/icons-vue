<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgvbcfb3d.css';
import '../../css/x/x_in5db1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vgvbcfb3d"/><path class="x_in5db1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tinfoil-light" /></template>
