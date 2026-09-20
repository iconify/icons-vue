<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/calya5bxg.css';
import '../../css/d/dq8f9xsoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="calya5bxg"/><path class="dq8f9xsoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center" /></template>
