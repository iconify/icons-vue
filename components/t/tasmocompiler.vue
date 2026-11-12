<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xghsn32in.css';
import '../../css/s/srz3brbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xghsn32in"/><path class="srz3brbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tasmocompiler" /></template>
