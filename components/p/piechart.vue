<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqqe5_blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bqqe5_blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:piechart" /></template>
