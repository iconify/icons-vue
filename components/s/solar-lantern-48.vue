<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn-0rhblv.css';
import '../../css/e/e3n6u6z4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sn-0rhblv"/><path class="e3n6u6z4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-lantern-48" /></template>
