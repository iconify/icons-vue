<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqxitkbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mqxitkbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:question-mark-circle-16-solid" /></template>
