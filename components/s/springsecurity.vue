<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v478rjvio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v478rjvio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:springsecurity" /></template>
