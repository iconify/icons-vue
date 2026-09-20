<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk7ayxbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk7ayxbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:strapi" /></template>
