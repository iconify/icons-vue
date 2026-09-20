<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijo7pnbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijo7pnbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:stpt" /></template>
