<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfl_6ccyr.css';
import '../../css/e/epc2a1c0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lfl_6ccyr"/><path class="epc2a1c0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-sharepoint-2013" /></template>
