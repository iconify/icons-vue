<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrf6z8bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrf6z8bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tmux" /></template>
