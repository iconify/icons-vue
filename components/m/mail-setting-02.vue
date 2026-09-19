<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xdw8tmbkh.css';
import '../../css/l/l5icpj83l.css';
import '../../css/e/ev0t_bbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xdw8tmbkh"/><path class="l5icpj83l"/><path class="ev0t_bbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-setting-02" /></template>
