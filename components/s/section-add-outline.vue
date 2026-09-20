<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouc5jvb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ouc5jvb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:section-add-outline" /></template>
