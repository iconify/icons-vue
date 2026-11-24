<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4q1sxb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4q1sxb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:netlify" /></template>
