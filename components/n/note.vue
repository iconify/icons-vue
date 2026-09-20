<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl3hgvb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl3hgvb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:note" /></template>
