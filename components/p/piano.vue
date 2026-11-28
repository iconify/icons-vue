<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic45bnbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic45bnbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:piano" /></template>
