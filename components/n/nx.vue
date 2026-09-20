<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5p-meb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5p-meb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nx" /></template>
