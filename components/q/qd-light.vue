<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxz6df3mx.css';
import '../../css/m/m1ai5425y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxz6df3mx"/><path class="m1ai5425y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qd-light" /></template>
