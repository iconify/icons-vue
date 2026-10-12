<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqr8yp28h.css';
import '../../css/b/blas98ktz.css';
import '../../css/m/mbe4uxbkg.css';
import '../../css/w/wrnacwbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fqr8yp28h"/><path class="blas98ktz"/><path class="mbe4uxbkg"/><path class="wrnacwbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:valve-wheel-48-bold" /></template>
