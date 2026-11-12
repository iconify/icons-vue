<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmrg6hbwc.css';
import '../../css/h/h7oxz0boa.css';
import '../../css/p/pvcco7a8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmrg6hbwc"/><path class="h7oxz0boa"/><path class="pvcco7a8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stirling-pdf-light" /></template>
