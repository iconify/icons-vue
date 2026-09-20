<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbkc6ef-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dbkc6ef-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:question-mark" /></template>
