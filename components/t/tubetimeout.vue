<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t69nwwbts.css';
import '../../css/d/dv8e4qb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t69nwwbts"/><path class="dv8e4qb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tubetimeout" /></template>
