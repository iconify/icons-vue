<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3-4ylime.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g3-4ylime"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:speaking-head" /></template>
