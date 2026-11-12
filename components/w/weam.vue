<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bogfzjklk.css';
import '../../css/q/qgbbpoxov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bogfzjklk"/><path class="qgbbpoxov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:weam" /></template>
