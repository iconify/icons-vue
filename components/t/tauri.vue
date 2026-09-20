<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkzjx8nae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkzjx8nae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tauri" /></template>
