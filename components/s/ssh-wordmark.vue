<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz5go1bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cz5go1bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ssh-wordmark" /></template>
