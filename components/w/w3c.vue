<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nze6iabmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nze6iabmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:w3c" /></template>
