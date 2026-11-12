<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynl1j0b_y.css';
import '../../css/s/s8or9-btt.css';
import '../../css/l/ln9fce54w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ynl1j0b_y"/><path class="s8or9-btt"/><path class="ln9fce54w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:redis-light" /></template>
