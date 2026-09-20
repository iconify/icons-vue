<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z277job2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z277job2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mitsubishi" /></template>
