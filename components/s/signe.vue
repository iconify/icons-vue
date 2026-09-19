<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzc1br60k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzc1br60k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:signe" /></template>
