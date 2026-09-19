<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/f/f1wfu4_qk.css';
import '../../css/y/y2m5b7byp.css';
import '../../css/k/krjghjbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="f1wfu4_qk"/><rect class="y2m5b7byp"/><path class="krjghjbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:milk-outline" /></template>
