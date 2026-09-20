<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n30y6gq7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n30y6gq7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:visualbasic" /></template>
