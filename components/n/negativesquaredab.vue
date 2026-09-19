<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou92kp7sw.css';
import '../../css/i/iobp--9yq.css';
import '../../css/f/fc129sozb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ou92kp7sw"/><path class="iobp--9yq"/><path class="fc129sozb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:negativesquaredab" /></template>
