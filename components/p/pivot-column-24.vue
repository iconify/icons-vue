<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jff5k-bht.css';
import '../../css/t/tpx4xacpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jff5k-bht"/><path class="tpx4xacpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pivot-column-24" /></template>
