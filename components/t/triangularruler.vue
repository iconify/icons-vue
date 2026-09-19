<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff_8p9-to.css';
import '../../css/e/e8au8db-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ff_8p9-to"/><path class="e8au8db-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:triangularruler" /></template>
