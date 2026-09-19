<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8ibeob9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":489,"height":512};
const content = `<path class="n8ibeob9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sophia" /></template>
