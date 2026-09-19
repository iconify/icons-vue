<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otlllccgn.css';
import '../../css/w/wtfmx7b3v.css';
import '../../css/t/tmj9w9mrh.css';
import '../../css/a/awt6j9brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="otlllccgn"/><g class="wtfmx7b3v"><path class="tmj9w9mrh"/><path class="awt6j9brq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:positive-dynamic" /></template>
