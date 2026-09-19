<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddpxg66go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddpxg66go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:piggy-bank-filled" /></template>
