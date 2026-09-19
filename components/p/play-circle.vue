<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2ahxob9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="f2ahxob9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:play-circle" /></template>
