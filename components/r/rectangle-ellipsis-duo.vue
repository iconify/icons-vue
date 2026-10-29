<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lx2-ubcjc.css';
import '../../css/g/g2qaiez3p.css';
import '../../css/x/xw_me4vft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lx2-ubcjc"/><path class="g2qaiez3p wm-a"/><path class="xw_me4vft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rectangle-ellipsis-duo" /></template>
