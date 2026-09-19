<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wt6ddqrsu.css';
import '../../css/y/yj8rovbyf.css';
import '../../css/v/vxg4v5b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="wt6ddqrsu"/><circle class="yj8rovbyf"/><path class="vxg4v5b-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:voicemail" /></template>
