<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsjoa2b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fsjoa2b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:milk" /></template>
