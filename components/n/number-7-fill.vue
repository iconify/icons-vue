<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec43ctbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ec43ctbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-7-fill" /></template>
