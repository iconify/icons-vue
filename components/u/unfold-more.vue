<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfwc8-bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfwc8-bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:unfold-more" /></template>
