<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/casyzt9mq.css';
import '../../css/g/gu5han_5f.css';
import '../../css/w/wjxv5acdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="casyzt9mq"><path class="gu5han_5f"/><path class="wjxv5acdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:selected" /></template>
