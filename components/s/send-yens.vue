<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnkf2h0mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnkf2h0mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:send-yens" /></template>
