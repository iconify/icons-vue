<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqo_rg33l.css';
import '../../css/j/jl229qvbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nqo_rg33l"/><path class="jl229qvbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pingora-proxy-manager-light" /></template>
