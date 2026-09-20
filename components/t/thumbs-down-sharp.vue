<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnqz1gbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnqz1gbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thumbs-down-sharp" /></template>
