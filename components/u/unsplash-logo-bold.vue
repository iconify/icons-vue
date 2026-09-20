<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4fw52b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4fw52b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:unsplash-logo-bold" /></template>
