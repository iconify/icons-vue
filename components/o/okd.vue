<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu_x1-bzu.css';
import '../../css/y/ys_vvx_-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iu_x1-bzu"/><path class="ys_vvx_-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:okd" /></template>
