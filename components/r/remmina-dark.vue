<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0c4prb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t0c4prb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:remmina-dark" /></template>
