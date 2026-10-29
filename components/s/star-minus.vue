<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv5n7ubdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv5n7ubdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:star-minus" /></template>
