<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aosvgyiyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1664};
const content = `<path class="aosvgyiyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thumbs-o-up" /></template>
