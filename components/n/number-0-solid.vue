<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deoxenb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="deoxenb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-0-solid" /></template>
