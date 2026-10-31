<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzbzq9bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzbzq9bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:timer-gloss" /></template>
