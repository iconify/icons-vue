<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_75cubyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_75cubyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-screen-lights" /></template>
