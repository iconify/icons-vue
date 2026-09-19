<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/g9w75jc3n.css';
import '../../css/y/yqxucbc0n.css';
import '../../css/m/m4wir9t-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="g9w75jc3n"/><path class="yqxucbc0n"/><path class="m4wir9t-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:volume-notice" /></template>
