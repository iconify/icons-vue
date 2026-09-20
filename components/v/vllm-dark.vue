<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7-mx-psp.css';
import '../../css/w/wgujkib2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r7-mx-psp"/><path class="wgujkib2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vllm-dark" /></template>
