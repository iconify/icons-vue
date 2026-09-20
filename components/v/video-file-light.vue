<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/q/qgeq1yd2g.css';
import '../../css/i/ilw2i8vqp.css';
import '../../css/g/g1h9-5bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="qgeq1yd2g"/><path class="ilw2i8vqp"/><path class="g1h9-5bhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:video-file-light" /></template>
