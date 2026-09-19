<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-dt4mq6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-dt4mq6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:virus-covid" /></template>
