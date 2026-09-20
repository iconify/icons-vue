<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed8jw0b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ed8jw0b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pyramid" /></template>
