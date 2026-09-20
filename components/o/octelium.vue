<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we9u1gzwf.css';
import '../../css/j/jf-7ccbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="we9u1gzwf"/><path class="jf-7ccbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octelium" /></template>
