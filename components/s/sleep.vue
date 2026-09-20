<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfgbu1m_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfgbu1m_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:sleep" /></template>
