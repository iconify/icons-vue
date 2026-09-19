<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu8h-ub7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mu8h-ub7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-copy" /></template>
