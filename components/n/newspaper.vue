<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d281nsb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="d281nsb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:newspaper" /></template>
