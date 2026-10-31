<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqja1p-lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqja1p-lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-letter-h" /></template>
