<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbnu5ip9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbnu5ip9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-minus-filled" /></template>
