<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf994ezlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pf994ezlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opengym-dark" /></template>
