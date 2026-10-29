<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ousr7gb-s.css';
import '../../css/s/s7at75-qv.css';
import '../../css/i/i0rs6rbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ousr7gb-s wm-k"/><path class="s7at75-qv wm-k"/><path class="i0rs6rbya wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:panel-left-close" /></template>
