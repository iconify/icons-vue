<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpi10xpow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpi10xpow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:type-italic" /></template>
