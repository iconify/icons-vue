<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnt04t58o.css';
import '../../css/e/e-q1i1bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnt04t58o"/><path class="e-q1i1bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxmox-helper-scripts-light" /></template>
