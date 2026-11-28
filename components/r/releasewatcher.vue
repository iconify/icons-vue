<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y653e0pli.css';
import '../../css/y/yol3kp1rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="y653e0pli"/><path class="yol3kp1rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:releasewatcher" /></template>
