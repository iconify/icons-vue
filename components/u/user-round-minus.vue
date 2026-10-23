<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6t456b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6t456b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-round-minus" /></template>
