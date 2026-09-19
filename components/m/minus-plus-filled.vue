<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecu-v9ahp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecu-v9ahp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:minus-plus-filled" /></template>
