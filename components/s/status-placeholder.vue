<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je0er7b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="je0er7b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:status-placeholder" /></template>
