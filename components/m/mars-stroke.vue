<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghv-0w7ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ghv-0w7ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mars-stroke" /></template>
