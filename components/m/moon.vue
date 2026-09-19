<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keqwgvb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="keqwgvb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:moon" /></template>
