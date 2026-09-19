<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um28_2kaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="um28_2kaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-9-circle-fill" /></template>
