<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj37qhm-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj37qhm-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-timer" /></template>
