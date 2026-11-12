<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdzw2qd4h.css';
import '../../css/y/yrbx-abvk.css';
import '../../css/t/tqets1biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdzw2qd4h"/><path class="yrbx-abvk"/><path class="tqets1biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-dark" /></template>
