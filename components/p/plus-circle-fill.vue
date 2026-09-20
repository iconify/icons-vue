<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la-8--b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="la-8--b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:plus-circle-fill" /></template>
