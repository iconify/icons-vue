<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e488r-b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e488r-b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:spoon-filled" /></template>
