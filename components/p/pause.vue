<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z46hmhu2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z46hmhu2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:pause" /></template>
