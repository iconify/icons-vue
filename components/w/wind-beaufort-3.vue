<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1nvo3hea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="k1nvo3hea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-3" /></template>
