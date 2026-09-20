<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urrrm4wfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="urrrm4wfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tidal-light" /></template>
