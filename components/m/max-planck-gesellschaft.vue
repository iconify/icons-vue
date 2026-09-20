<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4xp6obcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4xp6obcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:max-planck-gesellschaft" /></template>
