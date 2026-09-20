<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7t5hzqcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7t5hzqcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:weblate-dark" /></template>
