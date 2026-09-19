<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htym47wlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="htym47wlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:refresh" /></template>
