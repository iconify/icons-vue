<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm-s4bcxz.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/d/dfqmxp8ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm-s4bcxz"/><path class="bwibdw4bb"/><path class="dfqmxp8ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:meh-alt" /></template>
