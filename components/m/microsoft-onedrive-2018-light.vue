<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by00xob_x.css';
import '../../css/q/qhvaocbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="by00xob_x"/><path class="qhvaocbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onedrive-2018-light" /></template>
