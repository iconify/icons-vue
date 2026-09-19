<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-b6ff7_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-b6ff7_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:spotify" /></template>
