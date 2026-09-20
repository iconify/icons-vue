<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p39_dg31u.css';
import '../../css/l/lj93ifb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p39_dg31u"/><path class="lj93ifb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-mail-dark" /></template>
