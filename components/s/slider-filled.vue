<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h57226jer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h57226jer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:slider-filled" /></template>
