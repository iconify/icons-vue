<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/khy8p4b-y.css';
import '../../css/g/gmzwbacmo.css';
import '../../css/v/v7peg9b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="khy8p4b-y"/><path class="gmzwbacmo wm-k"/><path class="v7peg9b3t wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:settings-sketch" /></template>
