<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd4t30x-e.css';
import '../../css/q/qv-3h3qsp.css';
import '../../css/n/noh367bdh.css';
import '../../css/s/sx4huzrzr.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/b/b2e_3_bqx.css';
import '../../css/e/e_5vrebnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="sd4t30x-e"/><path class="qv-3h3qsp"/><path class="noh367bdh"/><path class="sx4huzrzr"/><g class="jn8qy4bru"><path class="b2e_3_bqx"/><path class="e_5vrebnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:nut-and-bolt" /></template>
