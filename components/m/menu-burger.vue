<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afkrn8b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afkrn8b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:menu-burger" /></template>
