<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h7lkx0ogu.css';
import '../../css/y/yzk23xbkf.css';
import '../../css/x/xq5yyvbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="h7lkx0ogu"/><path class="yzk23xbkf"/><path class="xq5yyvbkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-pause-outline" /></template>
