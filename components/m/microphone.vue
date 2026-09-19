<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwaa-wbbg.css';
import '../../css/j/jfmxxebmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwaa-wbbg"/><path class="jfmxxebmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone" /></template>
