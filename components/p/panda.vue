<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhb7xqbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="rhb7xqbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:panda" /></template>
