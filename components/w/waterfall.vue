<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx4izst4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx4izst4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:waterfall" /></template>
