<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrui74b0l.css';
import '../../css/r/r-3q_9bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vrui74b0l"/><path class="r-3q_9bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:toggle-off" /></template>
