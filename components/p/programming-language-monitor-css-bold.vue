<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wclz1cc_c.css';
import '../../css/c/czevaumet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wclz1cc_c"/><path class="czevaumet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:programming-language-monitor-css-bold" /></template>
