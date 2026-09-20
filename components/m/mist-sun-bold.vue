<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpxzpxbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpxzpxbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:mist-sun-bold" /></template>
