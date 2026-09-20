<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3lmlx16v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3lmlx16v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sparkle-2" /></template>
