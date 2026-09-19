<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6q-f6bnh.css';
import '../../css/l/lrignnb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6q-f6bnh"/><path class="lrignnb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:mood-very-good" /></template>
