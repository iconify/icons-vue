<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0t3ehl7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0t3ehl7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:minus-five-circle" /></template>
