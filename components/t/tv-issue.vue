<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/g/go7a7eb-c.css';
import '../../css/b/b482eebvh.css';
import '../../css/g/g5_p9yb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="go7a7eb-c"/><path class="b482eebvh"/><path class="g5_p9yb8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tv-issue" /></template>
