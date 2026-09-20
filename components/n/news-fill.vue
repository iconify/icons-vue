<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kajitxbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kajitxbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:news-fill" /></template>
