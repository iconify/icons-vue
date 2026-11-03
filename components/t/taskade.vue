<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh4z5kbri.css';
import '../../css/v/vhk8n-b7m.css';
import '../../css/h/hlbcq7bvh.css';
import '../../css/p/pdlb79bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vh4z5kbri"/><circle class="vhk8n-b7m"/><path class="hlbcq7bvh"/><path class="pdlb79bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:taskade" /></template>
