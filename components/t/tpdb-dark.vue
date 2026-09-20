<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq_ifjq_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq_ifjq_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tpdb-dark" /></template>
