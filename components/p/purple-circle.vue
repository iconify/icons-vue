<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spz3edb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="spz3edb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:purple-circle" /></template>
