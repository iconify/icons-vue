<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsw-bb_vv.css';
import '../../css/l/lv1nsoira.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsw-bb_vv"/><path class="lv1nsoira"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-ring" /></template>
