<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho98fkb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ho98fkb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:video-off" /></template>
