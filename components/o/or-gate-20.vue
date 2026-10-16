<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gza0lnxru.css';
import '../../css/l/lcdh-cbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gza0lnxru"/><path class="lcdh-cbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:or-gate-20" /></template>
