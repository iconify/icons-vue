<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aajt7uejw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aajt7uejw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:upvote" /></template>
