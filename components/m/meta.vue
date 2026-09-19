<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtd36i8-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtd36i8-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:meta" /></template>
