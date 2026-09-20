<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb74u2v9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb74u2v9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:moonscript" /></template>
