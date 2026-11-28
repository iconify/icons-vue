<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omisxpmjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omisxpmjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-heart" /></template>
