<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8o37xbsi.css';
import '../../css/o/ozhrcvezr.css';
import '../../css/n/nxg4h0b8x.css';
import '../../css/s/spa_47bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8o37xbsi"/><path class="ozhrcvezr"/><path class="nxg4h0b8x"/><path class="spa_47bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:maticx" /></template>
