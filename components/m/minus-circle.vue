<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzq0o3a5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzq0o3a5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:minus-circle" /></template>
