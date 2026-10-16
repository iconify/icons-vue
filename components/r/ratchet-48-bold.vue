<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsc_0ebep.css';
import '../../css/u/ukrjy-bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wsc_0ebep"/><path class="ukrjy-bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ratchet-48-bold" /></template>
