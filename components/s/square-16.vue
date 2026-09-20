<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjvaqbkij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kjvaqbkij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:square-16" /></template>
