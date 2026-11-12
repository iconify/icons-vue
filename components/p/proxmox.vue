<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yldie4v8a.css';
import '../../css/x/x7cs9_u7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yldie4v8a"/><path class="x7cs9_u7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxmox" /></template>
