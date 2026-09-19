<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6ghvs01x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6ghvs01x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tachometer-filled" /></template>
