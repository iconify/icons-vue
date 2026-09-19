<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ien_hybah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ien_hybah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shopping-bag" /></template>
