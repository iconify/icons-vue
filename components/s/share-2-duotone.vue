<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arbz2z5fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arbz2z5fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share-2-duotone" /></template>
