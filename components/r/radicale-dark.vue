<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdh-mkbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdh-mkbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radicale-dark" /></template>
