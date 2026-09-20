<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebe8fjn1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebe8fjn1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:triangle" /></template>
