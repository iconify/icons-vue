<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jelsw2bbk.css';
import '../../css/p/phs9k_bln.css';
import '../../css/t/tjav81vfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jelsw2bbk"/><path class="phs9k_bln"/><path class="tjav81vfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamyfin-dark" /></template>
