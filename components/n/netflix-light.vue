<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfoyfdche.css';
import '../../css/w/wxryjwb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfoyfdche"/><path class="wxryjwb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netflix-light" /></template>
