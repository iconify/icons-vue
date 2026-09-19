<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsd7b4a3r.css';
import '../../css/m/m6rsfj-rl.css';
import '../../css/a/a065enb7i.css';
import '../../css/r/ru0xozsfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tsd7b4a3r"/><path class="m6rsfj-rl"/><path class="a065enb7i"/><path class="ru0xozsfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:smileeyes" /></template>
