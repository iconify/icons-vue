<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux5n9jb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux5n9jb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-word" /></template>
