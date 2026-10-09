<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-y598bgk.css';
import '../../css/c/cuw48wy1a.css';
import '../../css/u/u5cct483i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y-y598bgk"/><path class="cuw48wy1a"/><path class="u5cct483i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:record-player-20" /></template>
