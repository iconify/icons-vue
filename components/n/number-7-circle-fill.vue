<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wipuycb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wipuycb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-7-circle-fill" /></template>
