<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3z55bfbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g3z55bfbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-top-right-and-question-mark" /></template>
