<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzf09n3ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzf09n3ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:neon" /></template>
