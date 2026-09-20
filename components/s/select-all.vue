<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny7m4gbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":18};
const content = `<path class="ny7m4gbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:select-all" /></template>
