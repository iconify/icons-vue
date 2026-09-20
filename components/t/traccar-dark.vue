<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmxz16h7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dmxz16h7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traccar-dark" /></template>
