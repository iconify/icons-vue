<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rhzqnybfy.css';
import '../../css/x/xwt_qrbis.css';
import '../../css/v/vhzi37bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rhzqnybfy"/><path class="xwt_qrbis"/><path class="vhzi37bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tissue-paper" /></template>
