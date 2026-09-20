<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y42_8l0eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y42_8l0eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trakt" /></template>
