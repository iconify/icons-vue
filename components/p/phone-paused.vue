<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp2--e48l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp2--e48l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone-paused" /></template>
