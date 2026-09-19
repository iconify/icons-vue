<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agw51bipm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agw51bipm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:zoom-minus" /></template>
