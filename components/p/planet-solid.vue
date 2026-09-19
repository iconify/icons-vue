<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-l1pd0_w.css';
import '../../css/b/brobnwmaq.css';
import '../../css/b/b7jxa2myi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path clip-rule="evenodd" class="brobnwmaq"/><path class="b7jxa2myi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:planet-solid" /></template>
