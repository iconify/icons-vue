<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuu6lyu_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuu6lyu_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:venus-fill-round" /></template>
