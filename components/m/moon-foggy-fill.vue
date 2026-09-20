<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erhuk9bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erhuk9bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:moon-foggy-fill" /></template>
