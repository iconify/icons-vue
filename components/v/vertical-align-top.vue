<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jihn21i9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jihn21i9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:vertical-align-top" /></template>
