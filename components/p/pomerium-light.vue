<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrcqh2b6o.css';
import '../../css/x/xw_9y5bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hrcqh2b6o"/><path class="xw_9y5bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pomerium-light" /></template>
