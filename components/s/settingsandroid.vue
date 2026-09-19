<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri4cqjboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ri4cqjboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:settingsandroid" /></template>
