<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfv5_ki6e.css';
import '../../css/i/iic3dfb3r.css';
import '../../css/w/wv8t68bmv.css';
import '../../css/v/vvmcp5lth.css';
import '../../css/q/qnwkdkb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wfv5_ki6e"/><path class="iic3dfb3r"/><path class="wv8t68bmv"/><path class="vvmcp5lth"/><path class="qnwkdkb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-access-dark" /></template>
