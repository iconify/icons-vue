<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd-4zjz7r.css';
import '../../css/o/ohm6g2bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pd-4zjz7r"/><circle class="ohm6g2bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:planet-outline" /></template>
