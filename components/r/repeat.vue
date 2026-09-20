<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_4_9lhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1_4_9lhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:repeat" /></template>
