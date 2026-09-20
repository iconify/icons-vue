<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz6q-0bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz6q-0bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mediamarkt" /></template>
