<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta7dw51we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ta7dw51we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-aquarius-duotone" /></template>
