<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qjjjy4boz.css';
import '../../css/m/mw0po8bwv.css';
import '../../css/i/i7y0tbbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qjjjy4boz"/><path class="mw0po8bwv"/><path class="i7y0tbbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:new-office" /></template>
