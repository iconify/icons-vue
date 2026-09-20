<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no54x2bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no54x2bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:v" /></template>
