<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv5f_v8gl.css';
import '../../css/m/mpb976b_h.css';
import '../../css/m/mbjqfdc5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pv5f_v8gl"/><path class="mpb976b_h"/><path class="mbjqfdc5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:template" /></template>
