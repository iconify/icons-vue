<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbyeonbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="vbyeonbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:wavy-dash" /></template>
