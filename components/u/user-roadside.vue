<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mn_gx6bsn.css';
import '../../css/s/shsaom4fn.css';
import '../../css/a/ak3jr5b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mn_gx6bsn"/><path class="shsaom4fn"/><path class="ak3jr5b-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-roadside" /></template>
