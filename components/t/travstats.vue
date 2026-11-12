<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob9sxvbzl.css';
import '../../css/w/wnxfwsbhv.css';
import '../../css/y/y87stwskn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ob9sxvbzl"/><path class="wnxfwsbhv"/><path class="y87stwskn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:travstats" /></template>
