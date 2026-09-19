<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te7bb6ppf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te7bb6ppf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:vials-solid" /></template>
