<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqqr7_ill.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqqr7_ill"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:snapchat-ghost" /></template>
