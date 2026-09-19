<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rhc1809ms.css';
import '../../css/p/pz77t9bmc.css';
import '../../css/a/aclgcfbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rhc1809ms"/><path class="pz77t9bmc"/><path class="aclgcfbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:transparency" /></template>
