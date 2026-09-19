<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivxlfrbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivxlfrbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:map" /></template>
