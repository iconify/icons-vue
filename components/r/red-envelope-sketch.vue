<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/ukwaa1bgs.css';
import '../../css/j/jq_nbg_-b.css';
import '../../css/s/seygyos_t.css';
import '../../css/n/neu8gqbky.css';
import '../../css/m/mqjsavxui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ukwaa1bgs"/><path class="jq_nbg_-b wm-a"/><path class="seygyos_t wm-k"/><path class="neu8gqbky wm-a"/><path class="mqjsavxui wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:red-envelope-sketch" /></template>
