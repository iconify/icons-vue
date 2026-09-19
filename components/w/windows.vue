<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti_jksrsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti_jksrsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:windows" /></template>
