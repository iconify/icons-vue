<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy42bub1l.css';
import '../../css/b/bm6480m4f.css';
import '../../css/j/j5tfbcb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy42bub1l"/><path class="bm6480m4f"/><path class="j5tfbcb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mqtt-fill" /></template>
