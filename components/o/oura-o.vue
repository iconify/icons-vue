<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hndqxpo_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hndqxpo_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:oura-o" /></template>
