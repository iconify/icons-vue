<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkx42b5na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkx42b5na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-12-small" /></template>
