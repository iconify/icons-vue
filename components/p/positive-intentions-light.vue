<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltfp6vbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ltfp6vbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:positive-intentions-light" /></template>
