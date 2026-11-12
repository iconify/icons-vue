<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk_y2-bpv.css';
import '../../css/k/k7rs5ub2m.css';
import '../../css/l/lpelvxbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bk_y2-bpv"/><path class="k7rs5ub2m"/><path class="lpelvxbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yabin" /></template>
