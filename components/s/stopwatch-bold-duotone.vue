<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szjj1eb9x.css';
import '../../css/y/y7btgy5eh.css';
import '../../css/i/isfz-28nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szjj1eb9x"/><path class="y7btgy5eh"/><path class="isfz-28nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-bold-duotone" /></template>
