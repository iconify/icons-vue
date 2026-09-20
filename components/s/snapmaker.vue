<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sducl6b4p.css';
import '../../css/r/rvcp9fbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sducl6b4p"/><path class="rvcp9fbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapmaker" /></template>
