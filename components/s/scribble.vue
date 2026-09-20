<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar93k-zbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar93k-zbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:scribble" /></template>
