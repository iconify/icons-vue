<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwh8_mg-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwh8_mg-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-comments" /></template>
