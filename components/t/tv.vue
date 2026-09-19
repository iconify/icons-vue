<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpb0q2cet.css';
import '../../css/l/l8k158baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hpb0q2cet"/><path class="l8k158baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:tv" /></template>
