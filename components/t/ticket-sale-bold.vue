<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3rkdqnsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3rkdqnsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ticket-sale-bold" /></template>
