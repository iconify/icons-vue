<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2px-ta7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c2px-ta7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:paper-airplane" /></template>
