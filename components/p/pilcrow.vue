<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-zn_rb4f.css';
import '../../css/v/vp_-scb_a.css';
import '../../css/i/ios73fbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k z-zn_rb4f"/><path class="vp_-scb_a wm-k"/><path class="ios73fbpx wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:pilcrow" /></template>
