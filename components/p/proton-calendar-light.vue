<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgvl_034t.css';
import '../../css/s/s-n0h6e4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgvl_034t"/><path class="s-n0h6e4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-calendar-light" /></template>
