<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy-pseb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy-pseb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:seek-next" /></template>
