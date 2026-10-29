<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jh6lxrb9u.css';
import '../../css/p/p8v2fyboy.css';
import '../../css/t/tzpvtdwuf.css';
import '../../css/x/xdetkr8ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jh6lxrb9u"/><path class="p8v2fyboy wm-s"/><path class="tzpvtdwuf wm-k"/><path class="wm-s xdetkr8ld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-incoming-sketch" /></template>
