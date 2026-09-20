<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdyn042hz.css';
import '../../css/l/lopv05qtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdyn042hz"/><path class="lopv05qtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nimtable-dark" /></template>
