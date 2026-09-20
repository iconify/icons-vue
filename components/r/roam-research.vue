<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2w32zbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2w32zbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:roam-research" /></template>
