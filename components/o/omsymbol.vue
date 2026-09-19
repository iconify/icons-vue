<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuoip9b-q.css';
import '../../css/i/i2wte8b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xuoip9b-q"/><path class="i2wte8b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:omsymbol" /></template>
