<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u83xm8bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u83xm8bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:telescope" /></template>
