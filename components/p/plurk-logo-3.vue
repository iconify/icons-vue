<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/i/i_lqrks1h.css';
import '../../css/h/h_79jpbkk.css';
import '../../css/b/bnpdgr2ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="i_lqrks1h"/><path class="h_79jpbkk"/><path class="bnpdgr2ia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:plurk-logo-3" /></template>
