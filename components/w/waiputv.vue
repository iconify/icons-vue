<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgssskbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgssskbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:waiputv" /></template>
