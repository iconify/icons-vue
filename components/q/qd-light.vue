<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxz6df3mx.css';
import '../../css/d/dg0y8obci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxz6df3mx"/><path class="dg0y8obci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qd-light" /></template>
