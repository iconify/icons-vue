<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o67rcdcet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o67rcdcet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sunrise" /></template>
