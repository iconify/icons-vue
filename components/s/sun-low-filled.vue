<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oys3y2b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oys3y2b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sun-low-filled" /></template>
