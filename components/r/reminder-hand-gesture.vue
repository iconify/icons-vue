<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vo6f34bpk.css';
import '../../css/x/xy9bvyb3v.css';
import '../../css/r/r51-_908r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vo6f34bpk"/><path class="xy9bvyb3v"/><path class="r51-_908r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:reminder-hand-gesture" /></template>
