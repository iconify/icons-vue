<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hitn88byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hitn88byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:sparkles-outline" /></template>
