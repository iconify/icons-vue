<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhtifodgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhtifodgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:symptoms-virus-lung-damage" /></template>
