<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlqc2v4ju.css';
import '../../css/e/e9f0v0bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jlqc2v4ju"/><path class="e9f0v0bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:share-20" /></template>
