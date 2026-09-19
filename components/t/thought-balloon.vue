<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au6wgzbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="au6wgzbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:thought-balloon" /></template>
