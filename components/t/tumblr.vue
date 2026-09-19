<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcuh318km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1664};
const content = `<path class="gcuh318km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tumblr" /></template>
