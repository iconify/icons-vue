<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knbz9_b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="knbz9_b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:person" /></template>
