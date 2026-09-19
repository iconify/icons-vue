<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egcpbkbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egcpbkbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:menu-fries" /></template>
