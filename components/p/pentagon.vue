<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbm_tg5ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbm_tg5ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:pentagon" /></template>
