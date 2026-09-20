<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xibp5enrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xibp5enrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smallstep-dark" /></template>
