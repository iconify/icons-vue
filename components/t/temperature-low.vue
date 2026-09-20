<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaxt9jb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaxt9jb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:temperature-low" /></template>
