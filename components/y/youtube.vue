<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edziozbwe.css';
import '../../css/x/xiw15t9pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edziozbwe"/><path class="xiw15t9pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:youtube" /></template>
