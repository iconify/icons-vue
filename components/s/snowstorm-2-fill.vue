<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imtb1zu4x.css';
import '../../css/n/nhxejibsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imtb1zu4x"/><path class="nhxejibsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowstorm-2-fill" /></template>
