<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0wybdbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0wybdbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:search-alert-filled" /></template>
