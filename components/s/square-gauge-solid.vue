<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7muh5ncn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7muh5ncn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-gauge-solid" /></template>
