<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl4z9ccue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl4z9ccue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:messenger-fill" /></template>
