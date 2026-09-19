<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9hqo-dhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h9hqo-dhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:phoenix-wordmark" /></template>
