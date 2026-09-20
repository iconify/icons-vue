<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsm66sbym.css';
import '../../css/q/qtg25xsmx.css';
import '../../css/n/n7ttdxber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsm66sbym"/><path class="qtg25xsmx"/><path class="n7ttdxber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:reddit-alien-alt" /></template>
