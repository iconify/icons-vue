<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg5qv8bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg5qv8bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:talenthouse" /></template>
