<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7f4pj88b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7f4pj88b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:v8-turbofan" /></template>
