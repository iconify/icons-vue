<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xqyp4q2de.css';
import '../../css/b/brqvdqb4k.css';
import '../../css/q/qiw5s9b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="xqyp4q2de"/><path class="brqvdqb4k"/><path class="qiw5s9b3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:transport" /></template>
