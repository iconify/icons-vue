<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef1ej922j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ef1ej922j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:microphone-slash-16-solid" /></template>
