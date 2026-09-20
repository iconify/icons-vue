<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqw92ubzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqw92ubzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:text-select" /></template>
