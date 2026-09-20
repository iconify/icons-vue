<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_cyjh5hd.css';
import '../../css/n/n75-9ccan.css';
import '../../css/g/g0good_0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n_cyjh5hd"><path class="n75-9ccan"/><path class="g0good_0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notification-bing" /></template>
