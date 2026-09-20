<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4x-fs84m.css';
import '../../css/u/uk7qgtbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w4x-fs84m"/><circle class="uk7qgtbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:map-pin" /></template>
