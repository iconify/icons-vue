<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvq7vy1ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvq7vy1ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-right-02" /></template>
