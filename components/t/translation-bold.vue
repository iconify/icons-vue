<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bfczqwbld.css';
import '../../css/b/bpv8bfbck.css';
import '../../css/s/sgvjp04ko.css';
import '../../css/s/swpqpacuo.css';
import '../../css/r/rwn4wowra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bfczqwbld"/><path class="bpv8bfbck"/><path class="sgvjp04ko"/><path class="swpqpacuo"/><path class="rwn4wowra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:translation-bold" /></template>
