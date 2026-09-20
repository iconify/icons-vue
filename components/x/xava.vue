<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8pln-eug.css';
import '../../css/m/mf521kb7u.css';
import '../../css/g/gj0x8hb9r.css';
import '../../css/x/xtyjrwb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8pln-eug"/><path class="mf521kb7u"/><path class="gj0x8hb9r"/><path class="xtyjrwb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xava" /></template>
