<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xkqyiwblc.css';
import '../../css/s/sd8wznb3i.css';
import '../../css/w/wolrz0b-c.css';
import '../../css/h/hadyfyrdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="xkqyiwblc"/><path class="sd8wznb3i"/><path class="wolrz0b-c"/><path class="hadyfyrdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:users-group-rounded-broken" /></template>
