<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_kod4b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_kod4b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:number-4-square-solid" /></template>
