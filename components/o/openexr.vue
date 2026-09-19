<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz9rk9b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":481,"height":512};
const content = `<path class="tz9rk9b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:openexr" /></template>
