<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg3tn20le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg3tn20le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:number-6-square-solid" /></template>
