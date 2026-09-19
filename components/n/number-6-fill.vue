<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1ot2ct4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1ot2ct4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-6-fill" /></template>
