<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd9-7xbqm.css';
import '../../css/i/i_d0_pb7z.css';
import '../../css/q/q73zetbak.css';
import '../../css/x/xkk6mccbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fd9-7xbqm"/><path class="i_d0_pb7z"/><path class="q73zetbak"/><path class="xkk6mccbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sensor-20-bold" /></template>
