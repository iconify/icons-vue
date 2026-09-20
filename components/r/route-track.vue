<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c8f47jrsp.css';
import '../../css/j/jnxuei71b.css';
import '../../css/h/hrm-hmbkx.css';
import '../../css/s/sdhzp1g3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c8f47jrsp"/><path clip-rule="evenodd" class="jnxuei71b"/><path class="hrm-hmbkx"/><path class="sdhzp1g3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:route-track" /></template>
