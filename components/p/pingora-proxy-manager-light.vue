<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rttpcbboh.css';
import '../../css/j/jl229qvbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rttpcbboh"/><path class="jl229qvbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pingora-proxy-manager-light" /></template>
