<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffwtwdbhy.css';
import '../../css/e/eh0t_9g0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffwtwdbhy"/><path class="eh0t_9g0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-kubewarden" /></template>
