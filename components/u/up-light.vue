<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6usx4t3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6usx4t3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:up-light" /></template>
