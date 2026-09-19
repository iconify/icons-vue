<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9xqzn69c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r9xqzn69c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:top-arrow" /></template>
