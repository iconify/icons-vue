<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gch9l5uyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gch9l5uyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panels-right-bottom-filled" /></template>
