<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfgr-6b4b.css';
import '../../css/q/q93ngmbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zfgr-6b4b"/><path class="q93ngmbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:notebook-48" /></template>
