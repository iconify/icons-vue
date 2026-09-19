<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwiag_bln.css';
import '../../css/w/wzeup5m6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwiag_bln"/><path class="wzeup5m6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rocket-alt" /></template>
