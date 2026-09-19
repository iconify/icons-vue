<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb0b3q3bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sb0b3q3bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-military-to-person" /></template>
