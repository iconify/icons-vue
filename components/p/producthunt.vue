<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fubs2opfz.css';
import '../../css/q/qxbtx8ztn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fubs2opfz"/><path class="qxbtx8ztn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:producthunt" /></template>
