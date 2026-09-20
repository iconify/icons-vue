<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0ots6rya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0ots6rya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:the-washington-post" /></template>
