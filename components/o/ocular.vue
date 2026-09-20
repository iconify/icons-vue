<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2nhvg7mm.css';
import '../../css/n/ny4n5ccbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j2nhvg7mm"/><path class="ny4n5ccbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ocular" /></template>
