<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvhxj1bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lvhxj1bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:microphone" /></template>
