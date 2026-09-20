<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox05h0bip.css';
import '../../css/t/t5n35bb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox05h0bip"/><path class="t5n35bb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xuanyuan" /></template>
