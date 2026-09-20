<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l37npu1fk.css';
import '../../css/s/sp_sykbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l37npu1fk"/><path class="sp_sykbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-rke" /></template>
