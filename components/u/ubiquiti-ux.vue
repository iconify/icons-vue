<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc6srw5lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc6srw5lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-ux" /></template>
