<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt8euk94d.css';
import '../../css/m/m3ld84doc.css';
import '../../css/d/dcwrwbboq.css';
import '../../css/h/hrrl0svrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt8euk94d wm-a"/><path class="m3ld84doc wm-k"/><path class="dcwrwbboq wm-k"/><path class="hrrl0svrj wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:telescope" /></template>
