<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcw_m1lcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcw_m1lcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mamba-ui" /></template>
