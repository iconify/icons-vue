<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe030ibzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xe030ibzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:octogon-filled-16" /></template>
