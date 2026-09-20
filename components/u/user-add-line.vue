<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb90z3lfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb90z3lfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-add-line" /></template>
