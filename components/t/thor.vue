<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4x3kxgfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f4x3kxgfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:thor" /></template>
