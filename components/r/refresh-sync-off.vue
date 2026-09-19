<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3vxfob2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":392};
const content = `<path class="g3vxfob2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:refresh-sync-off" /></template>
