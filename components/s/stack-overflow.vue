<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7eat9bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="k7eat9bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:stack-overflow" /></template>
