<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_0hbyvso.css';
import '../../css/s/ssv2g6b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_0hbyvso"/><path class="ssv2g6b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:real-debrid-light" /></template>
