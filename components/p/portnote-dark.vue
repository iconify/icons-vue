<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhp86_bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhp86_bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portnote-dark" /></template>
