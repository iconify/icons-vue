<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zh75_ac2u.css';
import '../../css/h/h616jyu9u.css';
import '../../css/i/ibuxjwbgw.css';
import '../../css/k/kyavumnzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zh75_ac2u"/><path class="h616jyu9u wm-a"/><path class="ibuxjwbgw wm-k"/><path class="kyavumnzm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:search-sketch" /></template>
