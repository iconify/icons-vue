<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eng9nmbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eng9nmbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ratatui" /></template>
