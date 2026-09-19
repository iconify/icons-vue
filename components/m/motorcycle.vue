<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ame5gh01i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1280};
const content = `<path class="ame5gh01i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:motorcycle" /></template>
