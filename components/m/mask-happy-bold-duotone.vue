<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwulmx5uf.css';
import '../../css/j/j07o9nb5s.css';
import '../../css/j/jlk36hbcb.css';
import '../../css/x/xcn7pebsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwulmx5uf"/><path class="j07o9nb5s"/><path class="jlk36hbcb"/><path class="xcn7pebsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mask-happy-bold-duotone" /></template>
