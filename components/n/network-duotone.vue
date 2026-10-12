<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/ztls5r9fg.css';
import '../../css/m/m3to96b8r.css';
import '../../css/v/vr5_g0bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ztls5r9fg"/><path class="m3to96b8r"/><path class="vr5_g0bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:network-duotone" /></template>
