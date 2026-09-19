<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/sguyahb_u.css';
import '../../css/y/ys9oqyb_w.css';
import '../../css/i/i8h8tzdlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="sguyahb_u"/><path class="ys9oqyb_w"/><path class="i8h8tzdlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:motion-01" /></template>
