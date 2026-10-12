<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9u0pyb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d9u0pyb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-strike-fill-20" /></template>
