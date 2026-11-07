<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfg6phm1t.css';
import '../../css/i/isfz-28nj.css';
import '../../css/s/szjj1eb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfg6phm1t"/><path class="isfz-28nj"/><path class="szjj1eb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-play-bold-duotone" /></template>
