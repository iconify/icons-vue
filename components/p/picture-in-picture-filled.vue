<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtubvubud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtubvubud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:picture-in-picture-filled" /></template>
