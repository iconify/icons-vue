<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrwimzbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":32};
const content = `<path class="jrwimzbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:ribbon" /></template>
