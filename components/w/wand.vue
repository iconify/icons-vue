<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftmjkabxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftmjkabxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wand" /></template>
