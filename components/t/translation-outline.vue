<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bfczqwbld.css';
import '../../css/b/bpv8bfbck.css';
import '../../css/s/sgvjp04ko.css';
import '../../css/s/swpqpacuo.css';
import '../../css/a/atdmbjg6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bfczqwbld"/><path class="bpv8bfbck"/><path class="sgvjp04ko"/><path class="swpqpacuo"/><path clip-rule="evenodd" class="atdmbjg6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:translation-outline" /></template>
