<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-any57sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p-any57sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:review-checkmark" /></template>
