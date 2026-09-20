<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8g-9jb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8g-9jb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pen-line" /></template>
