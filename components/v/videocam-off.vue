<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvlzdyfkb.css';
import '../../css/q/qm_k6gbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fvlzdyfkb"/><path class="qm_k6gbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:videocam-off" /></template>
