<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdaeq515n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdaeq515n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:versions-filled" /></template>
