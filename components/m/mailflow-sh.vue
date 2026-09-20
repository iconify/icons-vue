<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4t-70uyr.css';
import '../../css/v/vfekuobce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n4t-70uyr"/><path class="vfekuobce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailflow-sh" /></template>
