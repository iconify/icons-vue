<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmtc7c2_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hmtc7c2_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:number-1-square-solid" /></template>
