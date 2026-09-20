<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5n7i0b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5n7i0b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:steam-fill" /></template>
