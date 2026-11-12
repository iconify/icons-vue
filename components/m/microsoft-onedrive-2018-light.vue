<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuxcp-t-s.css';
import '../../css/q/qhvaocbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kuxcp-t-s"/><path class="qhvaocbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onedrive-2018-light" /></template>
