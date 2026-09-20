<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3hjm2bvy.css';
import '../../css/x/xc618m98j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f3hjm2bvy"/><path class="xc618m98j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notion" /></template>
