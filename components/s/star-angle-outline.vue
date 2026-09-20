<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb-9d2bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb-9d2bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-angle-outline" /></template>
