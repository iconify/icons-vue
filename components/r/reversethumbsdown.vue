<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de91r55gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="de91r55gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:reversethumbsdown" /></template>
