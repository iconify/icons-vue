<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv_1hsb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cv_1hsb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wrenchalt" /></template>
