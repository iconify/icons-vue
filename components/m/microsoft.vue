<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjjpr3yel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjjpr3yel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:microsoft" /></template>
