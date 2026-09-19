<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joaucm5om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joaucm5om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:tag" /></template>
