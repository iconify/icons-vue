<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t88_p75mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t88_p75mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tag-minus" /></template>
