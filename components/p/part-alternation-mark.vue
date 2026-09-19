<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz7v9cbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cz7v9cbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:part-alternation-mark" /></template>
