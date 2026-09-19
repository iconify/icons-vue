<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jh2j5sozv.css';
import '../../css/k/k38s6xbay.css';
import '../../css/u/uxt7hetvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jh2j5sozv"/><path class="k38s6xbay"/><path class="uxt7hetvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:save-one" /></template>
