<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy1rz-bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zy1rz-bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:smartphone-notch" /></template>
