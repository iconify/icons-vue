<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-261sbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-261sbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-6-circle-fill" /></template>
