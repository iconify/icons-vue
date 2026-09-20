<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqp1_dbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqp1_dbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:oven-mitts2-filled" /></template>
