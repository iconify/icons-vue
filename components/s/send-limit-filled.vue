<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxpr3ub_o.css';
import '../../css/y/y8q0_obwr.css';
import '../../css/u/ub3xs8bzt.css';
import '../../css/o/o3gn41opk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxpr3ub_o"/><path class="y8q0_obwr"/><path class="ub3xs8bzt"/><path class="o3gn41opk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:send-limit-filled" /></template>
