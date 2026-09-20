<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwjj5yv8t.css';
import '../../css/a/aj-0tlawi.css';
import '../../css/g/guah0xbpd.css';
import '../../css/g/gln5lwbrw.css';
import '../../css/i/it4ayvb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="mwjj5yv8t"/><circle class="aj-0tlawi"/><g class="guah0xbpd"><path class="gln5lwbrw"/><path class="it4ayvb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pkl" /></template>
