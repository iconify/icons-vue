<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1x-ibbak.css';
import '../../css/h/hlue_gbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v1x-ibbak"/><path class="hlue_gbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pellet-boiler-20-bold" /></template>
