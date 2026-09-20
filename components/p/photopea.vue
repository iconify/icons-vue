<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgc0-qnbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgc0-qnbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:photopea" /></template>
