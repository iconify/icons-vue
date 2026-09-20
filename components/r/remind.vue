<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvurxqbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nvurxqbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:remind" /></template>
