<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy28lqjna.css';
import '../../css/w/w4536acmd.css';
import '../../css/b/bnh_1x4bj.css';
import '../../css/g/gieo_eh2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iy28lqjna"/><path class="w4536acmd"/><path class="bnh_1x4bj"/><path class="gieo_eh2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sim-card-48" /></template>
