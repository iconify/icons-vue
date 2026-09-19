<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6yd7cbna.css';
import '../../css/x/xxps6nbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6yd7cbna"/><path class="xxps6nbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:station" /></template>
