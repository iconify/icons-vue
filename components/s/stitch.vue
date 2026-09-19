<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsezt0gyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsezt0gyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:stitch" /></template>
