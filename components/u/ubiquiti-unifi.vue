<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxfq3wdcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fxfq3wdcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ubiquiti-unifi" /></template>
