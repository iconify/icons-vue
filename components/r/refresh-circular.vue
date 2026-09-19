<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/l/l5i5hyb3b.css';
import '../../css/o/ozd_fxwmk.css';
import '../../css/k/k6cs5ab0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="shu3xdl9q"/><path class="l5i5hyb3b"/><path class="ozd_fxwmk"/><path class="k6cs5ab0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:refresh-circular" /></template>
