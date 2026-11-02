<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yihj--bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yihj--bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:play-football-fill" /></template>
