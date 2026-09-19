<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh_w85bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lh_w85bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:meeple-army" /></template>
