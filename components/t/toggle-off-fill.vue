<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt9gqfocz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lt9gqfocz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:toggle-off-fill" /></template>
