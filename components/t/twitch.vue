<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czz9dlbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="czz9dlbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:twitch" /></template>
