<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-4nj7z5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-4nj7z5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:megaphone-b-fill" /></template>
