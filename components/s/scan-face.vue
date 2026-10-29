<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/molcvsbva.css';
import '../../css/w/wl_z7s7lf.css';
import '../../css/x/xrey7damx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="molcvsbva wm-k"/><path class="wl_z7s7lf wm-a"/><path class="wm-a xrey7damx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:scan-face" /></template>
