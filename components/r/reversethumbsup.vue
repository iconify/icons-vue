<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7c79r05i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q7c79r05i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:reversethumbsup" /></template>
