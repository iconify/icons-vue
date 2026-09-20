<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th9qdhbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th9qdhbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:to-pip" /></template>
