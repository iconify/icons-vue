<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/err9aob5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="err9aob5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:obsidian" /></template>
