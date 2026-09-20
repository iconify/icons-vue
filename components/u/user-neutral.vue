<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjjo22bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rjjo22bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:user-neutral" /></template>
