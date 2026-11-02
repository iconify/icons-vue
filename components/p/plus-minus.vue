<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/d/d3f7vubre.css';
import '../../css/a/a-m7irbsn.css';
import '../../css/n/nn7ldeyao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="d3f7vubre"/><path class="a-m7irbsn"/><path class="nn7ldeyao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:plus-minus" /></template>
