<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaqd1-b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1088,"height":1792};
const content = `<path class="oaqd1-b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:odnoklassniki" /></template>
