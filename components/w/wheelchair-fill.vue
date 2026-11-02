<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c27w72jav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c27w72jav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wheelchair-fill" /></template>
