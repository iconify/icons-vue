<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gtmxuwkrn.css';
import '../../css/m/m717onbqp.css';
import '../../css/r/rx2lt8xhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gtmxuwkrn"/><path class="m717onbqp"/><path class="rx2lt8xhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:microphone-duotone" /></template>
