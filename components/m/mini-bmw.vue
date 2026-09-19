<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8m1s5y6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8m1s5y6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mini-bmw" /></template>
