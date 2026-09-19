<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvbqoqldh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvbqoqldh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:speaker-x-mark" /></template>
