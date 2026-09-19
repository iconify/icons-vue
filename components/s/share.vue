<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhh4_4chj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhh4_4chj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:share" /></template>
