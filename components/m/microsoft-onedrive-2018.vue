<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3a_m_e4a.css';
import '../../css/v/vcbqy5bsy.css';
import '../../css/k/kaoxaxu7c.css';
import '../../css/x/xd6m6dxve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d3a_m_e4a"/><path class="vcbqy5bsy"/><path class="kaoxaxu7c"/><path class="xd6m6dxve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onedrive-2018" /></template>
