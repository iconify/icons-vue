<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwlmx-b3y.css';
import '../../css/d/dlg1f9bpn.css';
import '../../css/v/vioal8b1j.css';
import '../../css/p/p_2y21whp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zwlmx-b3y"/><path class="dlg1f9bpn"/><path class="vioal8b1j"/><path class="p_2y21whp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:mint" /></template>
