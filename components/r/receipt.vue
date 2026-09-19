<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnebau0iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="hnebau0iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:receipt" /></template>
