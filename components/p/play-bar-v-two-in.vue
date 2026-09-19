<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rucr588rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rucr588rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:play-bar-v-two-in" /></template>
