<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q79mtubzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q79mtubzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:minus" /></template>
